<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbcy72b_r.css';
import '../../css/q/q66ufvz7x.css';
import '../../css/g/g2xe6acff.css';
import '../../css/q/qyd3s_92q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbcy72b_r"/><path class="q66ufvz7x"/><ellipse class="g2xe6acff"/><ellipse class="qyd3s_92q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:nutrition-outline" /></template>
