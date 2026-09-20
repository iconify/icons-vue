<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnpo3gbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnpo3gbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone-missed-solid" /></template>
