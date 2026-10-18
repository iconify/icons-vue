<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg3uv7bpl.css';
import '../../css/a/a921hcklm.css';
import '../../css/b/bht55acof.css';
import '../../css/u/um7961b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg3uv7bpl"/><path class="a921hcklm"/><path class="bht55acof"/><path class="um7961b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:net-metering-48" /></template>
