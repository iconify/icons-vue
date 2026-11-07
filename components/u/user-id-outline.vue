<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z75fauo-s.css';
import '../../css/j/js8ji6v_n.css';
import '../../css/l/lbf6xxfir.css';
import '../../css/r/rbayn2s6z.css';
import '../../css/b/b57ew5bmg.css';
import '../../css/u/uq39cqocs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z75fauo-s"/><path clip-rule="evenodd" class="js8ji6v_n"/><path class="lbf6xxfir"/><path class="rbayn2s6z"/><path class="b57ew5bmg"/><path clip-rule="evenodd" class="uq39cqocs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-id-outline" /></template>
