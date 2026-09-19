<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n64m8nfws.css';
import '../../css/o/oc_f315vi.css';
import '../../css/d/dg2xzd6cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n64m8nfws"/><path class="oc_f315vi"/><path class="dg2xzd6cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-in-manual-wheelchair-facing-right" /></template>
