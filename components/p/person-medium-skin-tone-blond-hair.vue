<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amn_b-_3e.css';
import '../../css/n/ncz70n-in.css';
import '../../css/b/bpvhhdbrl.css';
import '../../css/k/k39h0tblb.css';
import '../../css/y/y6fqwjbfy.css';
import '../../css/m/m-l90ob2o.css';
import '../../css/l/l_8clz36z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="amn_b-_3e"/><path class="ncz70n-in"/><path class="bpvhhdbrl"/><path class="k39h0tblb"/><path class="y6fqwjbfy"/><path class="m-l90ob2o"/><path class="l_8clz36z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-medium-skin-tone-blond-hair" /></template>
