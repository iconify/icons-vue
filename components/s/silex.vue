<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4x2-xb7r.css';
import '../../css/e/enyl_wbfz.css';
import '../../css/m/my_ui_fig.css';
import '../../css/v/vn1fcac6h.css';
import '../../css/k/k3yi_lb2l.css';
import '../../css/a/ary7yqs-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4x2-xb7r"/><path class="enyl_wbfz"/><path class="my_ui_fig"/><path class="vn1fcac6h"/><path class="k3yi_lb2l"/><path class="ary7yqs-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:silex" /></template>
