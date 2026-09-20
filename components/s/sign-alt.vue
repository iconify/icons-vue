<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esrpvgoqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esrpvgoqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sign-alt" /></template>
