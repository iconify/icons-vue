<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_2i5mwhi.css';
import '../../css/k/kqtb-7b7t.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged j_2i5mwhi"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged kqtb-7b7t"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:resource-pool-solid-badged" /></template>
