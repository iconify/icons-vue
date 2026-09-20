<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw7y2gnxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw7y2gnxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zerotier" /></template>
