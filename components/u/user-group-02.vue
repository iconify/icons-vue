<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/okbmw2brh.css';
import '../../css/c/c2pqo7bzq.css';
import '../../css/x/xm3lh5gcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="okbmw2brh"/><circle class="c2pqo7bzq"/><path class="xm3lh5gcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-group-02" /></template>
