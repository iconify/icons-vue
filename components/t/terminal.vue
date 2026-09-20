<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be0aebgqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be0aebgqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:terminal" /></template>
