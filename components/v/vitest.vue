<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7yr2gb8r.css';
import '../../css/i/if9yuik-y.css';
import '../../css/g/g3e_4lbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n7yr2gb8r"/><path class="if9yuik-y"/><path class="g3e_4lbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vitest" /></template>
