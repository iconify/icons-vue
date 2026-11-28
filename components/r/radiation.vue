<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7a_yubni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7a_yubni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:radiation" /></template>
