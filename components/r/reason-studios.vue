<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnmz7triw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnmz7triw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:reason-studios" /></template>
