<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3__ojbef.css';
import '../../css/u/u9lqayb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3__ojbef"/><path clip-rule="evenodd" class="u9lqayb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-q-filled" /></template>
