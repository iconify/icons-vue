<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha_zp6bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha_zp6bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tag-alt-filled" /></template>
