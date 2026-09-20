<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxc_ccc7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxc_ccc7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:package-box-fill" /></template>
