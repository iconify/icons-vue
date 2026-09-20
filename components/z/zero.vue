<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvu1scc_a.css';
import '../../css/k/kh1pia80p.css';
import '../../css/a/aun6_3zku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvu1scc_a"/><path clip-rule="evenodd" class="kh1pia80p"/><path class="aun6_3zku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zero" /></template>
