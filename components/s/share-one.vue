<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tnc833_np.css';
import '../../css/a/ayj3gb6gy.css';
import '../../css/t/t-q_z3btq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5WDjaeZP"><g class="v3_i3wktz"><path class="tnc833_np"/><path class="ayj3gb6gy"/><path class="t-q_z3btq"/></g></mask></defs><path mask="url(#SVG5WDjaeZP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:share-one" /></template>
