<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn9ufwz-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn9ufwz-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mic" /></template>
