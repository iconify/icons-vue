<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqjikdywo.css';
import '../../css/b/b2d36xbqv.css';
import '../../css/l/lis884bqb.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-outline--badged clr-i-outline-path-1--badged rqjikdywo"/><path class="b2d36xbqv clr-i-outline--badged clr-i-outline-path-2--badged"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged lis884bqb"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tags-outline-badged" /></template>
