<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piu2dnbsw.css';
import '../../css/q/qapg4nbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piu2dnbsw"/><path clip-rule="evenodd" class="qapg4nbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:png" /></template>
