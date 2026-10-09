<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwjp_wt2n.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/f/fk_ahtbzo.css';
import '../../css/b/b325a1bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zwjp_wt2n"/><path class="aqsnv9bnd"/><path class="fk_ahtbzo"/><path class="b325a1bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-x-20-bold" /></template>
