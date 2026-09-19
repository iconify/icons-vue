<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bujcfabcl.css';
import '../../css/p/p68_n_bch.css';
import '../../css/r/riwp_rwvj.css';
import '../../css/u/u04jombws.css';
import '../../css/x/x5rsn2cfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bujcfabcl"/><path class="p68_n_bch"/><path class="riwp_rwvj"/><path class="u04jombws"/><path class="x5rsn2cfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:unity-wordmark" /></template>
