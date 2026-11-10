<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1tp18z4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1tp18z4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-x-mark" /></template>
