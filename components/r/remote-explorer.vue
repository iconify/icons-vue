<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1gahrb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="l1gahrb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:remote-explorer" /></template>
