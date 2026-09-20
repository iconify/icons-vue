<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab3zrzlrq.css';
import '../../css/b/bldxs_3nx.css';
import '../../css/k/k5dgsrbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab3zrzlrq"/><path class="bldxs_3nx"/><path class="k5dgsrbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:media" /></template>
