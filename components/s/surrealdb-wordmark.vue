<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywy3-kbcp.css';
import '../../css/h/hdkj9ybxw.css';
import '../../css/x/xpwcu5bdd.css';
import '../../css/t/tid_x98uq.css';
import '../../css/b/b5c7ocbpx.css';
import '../../css/p/p9_dk52ys.css';
import '../../css/v/vissfdb5s.css';
import '../../css/f/fyr47cbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ywy3-kbcp"/><path class="hdkj9ybxw"/><path class="xpwcu5bdd"/><path class="tid_x98uq"/><path class="b5c7ocbpx"/><path class="p9_dk52ys"/><path class="vissfdb5s"/><path class="fyr47cbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:surrealdb-wordmark" /></template>
