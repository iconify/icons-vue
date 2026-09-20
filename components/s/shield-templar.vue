<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkf-k8b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkf-k8b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-templar" /></template>
