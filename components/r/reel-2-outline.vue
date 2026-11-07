<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcs6tehmj.css';
import '../../css/m/ml1bsrb5l.css';
import '../../css/f/fsv_d9evq.css';
import '../../css/d/dkkib-ewx.css';
import '../../css/v/ve8higxbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcs6tehmj"/><path class="ml1bsrb5l"/><path class="fsv_d9evq"/><path class="dkkib-ewx"/><path class="ve8higxbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reel-2-outline" /></template>
