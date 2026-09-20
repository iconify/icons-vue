<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt4ygg3jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt4ygg3jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:octagon-danger" /></template>
