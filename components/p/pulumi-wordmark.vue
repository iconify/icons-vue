<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tacaomvbw.css';
import '../../css/c/ckfmp0bvq.css';
import '../../css/y/yi7l1_bae.css';
import '../../css/b/brv_2tt_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tacaomvbw"/><path class="ckfmp0bvq"/><path class="yi7l1_bae"/><path class="brv_2tt_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pulumi-wordmark" /></template>
