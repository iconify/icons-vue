<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_6bn_bwc.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b_6bn_bwc clr-i-outline--alerted clr-i-outline-path-1--alerted"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-2--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:resource-pool-outline-alerted" /></template>
