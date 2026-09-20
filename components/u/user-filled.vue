<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idhh4wbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idhh4wbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-filled" /></template>
