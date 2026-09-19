<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u63daxw1l.css';
import '../../css/d/daxtkab1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u63daxw1l"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:medium-outline" /></template>
