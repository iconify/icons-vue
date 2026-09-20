<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlsj-shoz.css';
import '../../css/o/o3426z_bo.css';
import '../../css/d/d9xp_nb_i.css';
import '../../css/d/ddax3ubiv.css';
import '../../css/f/f9dk4hqsd.css';
import '../../css/f/fu8bnzmoi.css';
import '../../css/g/gkv74ho0z.css';
import '../../css/i/i4ap3jmmp.css';
import '../../css/a/ai5o2dggb.css';
import '../../css/c/co0orhbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zlsj-shoz"/><path class="o3426z_bo"/><path class="d9xp_nb_i"/><path class="ddax3ubiv"/><path class="f9dk4hqsd"/><path class="fu8bnzmoi"/><path class="gkv74ho0z"/><path class="i4ap3jmmp"/><path class="ai5o2dggb"/><path class="co0orhbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:pear" /></template>
