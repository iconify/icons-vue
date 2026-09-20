<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi33hccvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi33hccvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:square-enix" /></template>
