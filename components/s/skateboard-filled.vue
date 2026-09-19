<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksw9zbbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksw9zbbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skateboard-filled" /></template>
