<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-7eu8rv.css';
import '../../css/f/f84x_gb3e.css';
import '../../css/o/of7d1zb9r.css';
import '../../css/z/zkgcdgrpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v4-7eu8rv"/><circle class="f84x_gb3e"/><circle class="of7d1zb9r"/><path class="zkgcdgrpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sad" /></template>
