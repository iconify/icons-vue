<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhln8idvw.css';
import '../../css/k/k7yugubqn.css';
import '../../css/x/xggoo1bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhln8idvw"/><path class="k7yugubqn"/><path clip-rule="evenodd" class="xggoo1bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-plus-outline" /></template>
