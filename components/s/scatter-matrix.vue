<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc5thce2f.css';
import '../../css/x/xo1yjrb5w.css';
import '../../css/w/wk9a195np.css';
import '../../css/x/x0qkfr1ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="xc5thce2f"/><circle class="xo1yjrb5w"/><circle class="wk9a195np"/><path class="x0qkfr1ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scatter-matrix" /></template>
