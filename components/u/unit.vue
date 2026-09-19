<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irb-tcb5g.css';
import '../../css/k/kt2e20byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23.3,"height":25.7};
const content = `<path class="irb-tcb5g"/><path class="kt2e20byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:unit" /></template>
