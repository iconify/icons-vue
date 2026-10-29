<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8quyib2t.css';
import '../../css/k/kw4-qabzh.css';
import '../../css/t/tdwbu_b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8quyib2t wm-a"/><path class="kw4-qabzh wm-a"/><path class="tdwbu_b5f wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:volleyball" /></template>
