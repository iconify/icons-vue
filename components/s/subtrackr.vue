<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_-dcbbxg.css';
import '../../css/b/b9nh0sb1l.css';
import '../../css/l/lv_7odbrh.css';
import '../../css/i/ivu5h9bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_-dcbbxg"/><path class="b9nh0sb1l"/><path class="lv_7odbrh"/><path class="ivu5h9bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subtrackr" /></template>
