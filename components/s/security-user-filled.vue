<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-k_f2b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-k_f2b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:security-user-filled" /></template>
