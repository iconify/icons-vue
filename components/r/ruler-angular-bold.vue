<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aytzwvbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aytzwvbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-angular-bold" /></template>
