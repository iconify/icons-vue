<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1cyrmb8e.css';
import '../../css/m/mvssxhbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1cyrmb8e"/><path class="mvssxhbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pencil-writing-duotone" /></template>
