<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg4rw_iiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg4rw_iiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nxp" /></template>
