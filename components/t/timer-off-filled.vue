<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgkfl6b7g.css';
import '../../css/t/t2vwib_3k.css';
import '../../css/z/zka-lh4oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgkfl6b7g"/><path clip-rule="evenodd" class="t2vwib_3k"/><path class="zka-lh4oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:timer-off-filled" /></template>
