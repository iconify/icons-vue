<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-f-t5b3k.css';
import '../../css/j/jn6f5yb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-f-t5b3k"/><path clip-rule="evenodd" class="jn6f5yb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:zoom-in-outline" /></template>
