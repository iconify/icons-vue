<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2-tk3beh.css';
import '../../css/m/my7j9r31x.css';
import '../../css/j/jvw28gbdo.css';
import '../../css/v/vmlmfg8oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2-tk3beh"/><path class="my7j9r31x"/><path class="jvw28gbdo"/><path class="vmlmfg8oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:printer" /></template>
