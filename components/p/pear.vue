<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cqn6g1bhd.css';
import '../../css/w/w1ex1ky4b.css';
import '../../css/c/c0m8i--rf.css';
import '../../css/p/pty22pbyc.css';
import '../../css/n/nengl2b3m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmJCgO9BY"><g class="ft5dv1b6b"><path class="cqn6g1bhd"/><path class="w1ex1ky4b"/><circle class="c0m8i--rf"/><circle class="pty22pbyc"/><circle class="nengl2b3m"/></g></mask></defs><path mask="url(#SVGmJCgO9BY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pear" /></template>
