<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpv7zboci.css';
import '../../css/c/chqabwsoe.css';
import '../../css/b/bqkka_ykq.css';
import '../../css/k/kyiokicbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zpv7zboci"/><path class="chqabwsoe"/><path class="bqkka_ykq"/><path class="kyiokicbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:satellite-dish-48-bold" /></template>
