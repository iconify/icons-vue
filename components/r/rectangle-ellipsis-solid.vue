<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu2bbhn-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu2bbhn-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rectangle-ellipsis-solid" /></template>
