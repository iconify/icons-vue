<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utpq3jyxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utpq3jyxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:siren-fill-round" /></template>
