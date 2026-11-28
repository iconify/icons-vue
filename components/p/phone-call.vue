<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iin1szbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iin1szbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:phone-call" /></template>
