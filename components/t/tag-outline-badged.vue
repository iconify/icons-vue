<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey47n4bde.css';
import '../../css/a/ayiij3brd.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-outline--badged clr-i-outline-path-1--badged ey47n4bde"/><path class="ayiij3brd clr-i-outline--badged clr-i-outline-path-2--badged"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tag-outline-badged" /></template>
