<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_t84-b5u.css';
import '../../css/b/bx7-e6irj.css';
import '../../css/r/rd_-p8eew.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged x_t84-b5u"/><path class="bx7-e6irj clr-i-solid--badged clr-i-solid-path-2--badged"/><path class="clr-i-solid--badged clr-i-solid-path-3--badged rd_-p8eew"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:world-solid-badged" /></template>
