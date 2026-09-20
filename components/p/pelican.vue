<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyoei_wsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyoei_wsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pelican" /></template>
