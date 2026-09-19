<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kehrhwx8k.css';
import '../../css/d/dbnvdzh6r.css';
import '../../css/t/t6qhtnnfm.css';
import '../../css/c/coyv17mlx.css';
import '../../css/c/cnusf2bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kehrhwx8k"/><path class="dbnvdzh6r"/><path class="t6qhtnnfm"/><path class="coyv17mlx"/><path class="cnusf2bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rspec-wordmark" /></template>
