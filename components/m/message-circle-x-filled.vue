<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzj-vlb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzj-vlb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-x-filled" /></template>
