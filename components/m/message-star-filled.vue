<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x45u8ng5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x45u8ng5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-star-filled" /></template>
