<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/i/i_-8rn_4z.css';
import '../../css/v/v_fpkcbui.css';
import '../../css/k/kcex68bds.css';
import '../../css/o/ofkzbwboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="i_-8rn_4z"/><path class="v_fpkcbui"/><path class="kcex68bds"/><path class="ofkzbwboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:wallet" /></template>
