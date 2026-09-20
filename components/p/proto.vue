<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn0f-q-la.css';
import '../../css/i/iouu_3bvv.css';
import '../../css/p/p2maqeerx.css';
import '../../css/a/asuv_t_id.css';
import '../../css/j/jh6vui6je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fn0f-q-la"/><path class="iouu_3bvv"/><path class="p2maqeerx"/><path class="asuv_t_id"/><path class="jh6vui6je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:proto" /></template>
