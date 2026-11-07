<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vskr90bqk.css';
import '../../css/k/kdjsh1b9r.css';
import '../../css/j/jlmj2df4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vskr90bqk"/><path class="kdjsh1b9r"/><path class="jlmj2df4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboard-bold" /></template>
