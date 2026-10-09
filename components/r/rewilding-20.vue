<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb9hcvbsg.css';
import '../../css/n/n28q9qbfx.css';
import '../../css/l/lbw0b8b1k.css';
import '../../css/l/lvrhn6scz.css';
import '../../css/s/sd4bh2f7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xb9hcvbsg"/><path class="n28q9qbfx"/><path class="lbw0b8b1k"/><path class="lvrhn6scz"/><path class="sd4bh2f7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rewilding-20" /></template>
