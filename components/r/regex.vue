<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/e5l2t5bnm.css';
import '../../css/k/ka162yg0t.css';
import '../../css/p/pwqhvxb2x.css';
import '../../css/z/zbgq8xytk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="e5l2t5bnm wm-shadow"/><path class="ka162yg0t wm-shadow"/><path class="pwqhvxb2x"/><path class="zbgq8xytk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:regex" /></template>
