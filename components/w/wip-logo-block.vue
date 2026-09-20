<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0gv3ezgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0gv3ezgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wip-logo-block" /></template>
