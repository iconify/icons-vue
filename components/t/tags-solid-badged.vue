<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp1mmybuc.css';
import '../../css/l/lis884bqb.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged jp1mmybuc"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged lis884bqb"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tags-solid-badged" /></template>
