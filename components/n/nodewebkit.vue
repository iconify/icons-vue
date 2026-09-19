<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yni9wjbvy.css';
import '../../css/p/ppahphbla.css';
import '../../css/l/luhpwmbsn.css';
import '../../css/m/m9vou0fxn.css';
import '../../css/n/nsuhtqbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yni9wjbvy"/><path class="ppahphbla"/><path class="luhpwmbsn"/><path class="m9vou0fxn"/><path class="nsuhtqbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nodewebkit" /></template>
