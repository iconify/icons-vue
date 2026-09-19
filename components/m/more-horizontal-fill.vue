<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1xy6nh9u.css';
import '../../css/d/dq12o7ykb.css';
import '../../css/b/b74ikwezj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n1xy6nh9u"/><circle class="dq12o7ykb"/><circle class="b74ikwezj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:more-horizontal-fill" /></template>
