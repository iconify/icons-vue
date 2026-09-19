<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eetpvy9gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eetpvy9gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:radio-filled" /></template>
