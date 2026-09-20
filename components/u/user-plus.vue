<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbeaf3bzp.css';
import '../../css/i/iik-bbx6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbeaf3bzp"/><path class="iik-bbx6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-plus" /></template>
