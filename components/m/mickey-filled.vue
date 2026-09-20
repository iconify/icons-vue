<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5aw93b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5aw93b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mickey-filled" /></template>
