<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6vzrquwp.css';
import '../../css/k/k_0sx3bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6vzrquwp"/><path class="k_0sx3bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:projector-filled" /></template>
