<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6_co1nfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6_co1nfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nfc" /></template>
