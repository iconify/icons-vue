<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blpec2f_v.css';
import '../../css/p/pwrb__blp.css';
import '../../css/g/g1qd2ab1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="blpec2f_v"/><path class="pwrb__blp"/><path class="g1qd2ab1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stargazing-48" /></template>
