<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i24lvpsxg.css';
import '../../css/k/kv_lf4f7r.css';
import '../../css/x/xmfmqwpbn.css';
import '../../css/i/iwgm76bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i24lvpsxg"/><path class="kv_lf4f7r"/><path class="xmfmqwpbn"/><path class="iwgm76bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mic-off-20-bold" /></template>
