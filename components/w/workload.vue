<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5_ojsbrt.css';
import '../../css/q/qesa7pb9s.css';
import '../../css/b/biog0ibqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5_ojsbrt"/><path class="qesa7pb9s"/><path class="biog0ibqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:workload" /></template>
