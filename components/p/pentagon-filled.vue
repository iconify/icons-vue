<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0mc6achg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0mc6achg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pentagon-filled" /></template>
