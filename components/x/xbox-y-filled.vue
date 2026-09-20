<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spyss-1is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spyss-1is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:xbox-y-filled" /></template>
