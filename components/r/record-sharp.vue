<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diy7rja_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diy7rja_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:record-sharp" /></template>
