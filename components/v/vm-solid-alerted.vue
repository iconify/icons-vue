<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2wr_lqly.css';
import '../../css/c/cyf6ddbft.css';
import '../../css/i/i4sbciq0b.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b2wr_lqly clr-i-solid--alerted clr-i-solid-path-1--alerted"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted cyf6ddbft"/><path class="clr-i-solid--alerted clr-i-solid-path-3--alerted i4sbciq0b"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:vm-solid-alerted" /></template>
