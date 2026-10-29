<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi6qjf9kl.css';
import '../../css/r/r2g9dxfqu.css';
import '../../css/q/qkesd0bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi6qjf9kl"/><path class="r2g9dxfqu"/><path class="qkesd0bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:ticket" /></template>
