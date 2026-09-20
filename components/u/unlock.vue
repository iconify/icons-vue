<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an-s6zb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an-s6zb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:unlock" /></template>
