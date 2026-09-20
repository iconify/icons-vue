<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzf8o-bpc.css';
import '../../css/l/lkt4b8bkv.css';
import '../../css/t/tncpom-al.css';
import '../../css/o/o2i8a6buf.css';
import '../../css/a/awnap3_pg.css';
import '../../css/p/p7c_clb3p.css';
import '../../css/j/j980odbda.css';
import '../../css/g/gipwh9_9j.css';
import '../../css/y/ytvhngqbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="gzf8o-bpc"/><circle class="lkt4b8bkv"/><path class="tncpom-al"/><path class="o2i8a6buf"/><path class="awnap3_pg"/><circle class="p7c_clb3p"/><circle class="j980odbda"/><circle class="gipwh9_9j"/><circle class="ytvhngqbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:timer" /></template>
