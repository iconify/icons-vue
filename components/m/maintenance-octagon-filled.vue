<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twiaix3mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twiaix3mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-octagon-filled" /></template>
