<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch4n5t7zo.css';
import '../../css/s/sg3wzf9dj.css';
import '../../css/z/z186-4zir.css';
import '../../css/r/rh12-tjpm.css';
import '../../css/o/ogh868b0i.css';
import '../../css/f/fof12qgdq.css';
import '../../css/a/apidwjb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ch4n5t7zo"/><path class="sg3wzf9dj"/><circle class="z186-4zir"/><circle class="rh12-tjpm"/><circle class="ogh868b0i"/><circle class="fof12qgdq"/><circle class="apidwjb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:podium-with-audience" /></template>
