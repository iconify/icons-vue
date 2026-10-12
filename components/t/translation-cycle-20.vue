<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfd6n_b5f.css';
import '../../css/h/h7y14-blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hfd6n_b5f"/><path class="h7y14-blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-cycle-20" /></template>
