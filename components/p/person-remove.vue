<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/i/izvovy.css';
import '../../css/f/f-8s9h.css';
import '../../css/u/u2yb_n.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c izvovy"/><path class="a0m25c f-8s9h"/><path class="a0m25c u2yb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:person-remove" /></template>
