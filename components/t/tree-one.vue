<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/i/i5lwzjcxg.css';
import '../../css/b/bpt2z3gew.css';
import '../../css/t/thz3lmbza.css';
import '../../css/d/dhxko4tgr.css';
import '../../css/o/o_s4hwb4m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPbaNNcyr"><g class="s9cl3zbei"><ellipse class="i5lwzjcxg"/><path class="bpt2z3gew"/><path class="thz3lmbza"/><path class="dhxko4tgr"/><path class="o_s4hwb4m"/></g></mask></defs><path mask="url(#SVGPbaNNcyr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tree-one" /></template>
