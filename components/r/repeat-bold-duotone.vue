<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6iijhcww.css';
import '../../css/x/xq74wrb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6iijhcww"/><path class="xq74wrb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-bold-duotone" /></template>
