<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuzhc5bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzhc5bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plus-filled" /></template>
