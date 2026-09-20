<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vukvxzvmz.css';
import '../../css/f/fyt8axbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vukvxzvmz"/><path class="fyt8axbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:pediatrics" /></template>
