<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpykv1bud.css';
import '../../css/o/o760gtbbr.css';
import '../../css/l/lmf0ecbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rpykv1bud"/><path class="o760gtbbr"/><circle class="lmf0ecbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tape-drive-solid-badged" /></template>
