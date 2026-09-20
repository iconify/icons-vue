<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ary7gubza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ary7gubza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:noise-reduction" /></template>
