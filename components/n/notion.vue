<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cliop5bpn.css';
import '../../css/n/n4tmlp77t.css';
import '../../css/p/pmy0i-b4f.css';
import '../../css/p/p7kcwhk_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cliop5bpn"/><path class="n4tmlp77t"/><path class="pmy0i-b4f"/><path class="p7kcwhk_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:notion" /></template>
