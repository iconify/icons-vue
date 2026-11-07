<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixkakeb2a.css';
import '../../css/i/ia9jguu5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixkakeb2a"/><path clip-rule="evenodd" class="ia9jguu5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-trash-bold" /></template>
