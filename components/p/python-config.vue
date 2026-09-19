<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnh7u9f3r.css';
import '../../css/t/t_2lkqbxb.css';
import '../../css/n/nmjmojrlk.css';
import '../../css/s/s_619eb4q.css';
import '../../css/b/biiv_obtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gnh7u9f3r"/><g class="t_2lkqbxb"><path class="nmjmojrlk"/><path class="s_619eb4q"/><path class="biiv_obtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:python-config" /></template>
