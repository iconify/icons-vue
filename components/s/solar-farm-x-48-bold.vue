<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luevgzb2b.css';
import '../../css/z/zrlocwb7c.css';
import '../../css/p/p7uzcdb2n.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="luevgzb2b"/><path class="zrlocwb7c"/><path class="p7uzcdb2n"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-x-48-bold" /></template>
