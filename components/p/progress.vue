<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn9-81bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn9-81bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:progress" /></template>
