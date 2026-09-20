<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dujmnu_mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dujmnu_mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:vertical-switch-long" /></template>
