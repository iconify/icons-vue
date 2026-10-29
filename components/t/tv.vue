<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjq-6db1p.css';
import '../../css/s/st7bm40ae.css';
import '../../css/m/mz609cc_k.css';
import '../../css/e/ea6yb7buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjq-6db1p wm-a"/><path class="st7bm40ae wm-k"/><path class="mz609cc_k wm-k"/><path class="ea6yb7buv wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:tv" /></template>
