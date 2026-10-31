<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdftbpbaj.css';
import '../../css/j/j4lu8gyen.css';
import '../../css/q/qmrxzvmyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="wdftbpbaj"/><path class="j4lu8gyen"/><path class="qmrxzvmyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:samoa" /></template>
