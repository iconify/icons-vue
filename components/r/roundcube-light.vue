<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmbgd7baw.css';
import '../../css/k/kczhvw7ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmbgd7baw"/><path class="kczhvw7ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roundcube-light" /></template>
