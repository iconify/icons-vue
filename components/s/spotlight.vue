<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpcbndban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpcbndban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spotlight" /></template>
