<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kotjj9zeu.css';
import '../../css/x/xt-rj2biq.css';
import '../../css/p/py7p1oj7p.css';
import '../../css/g/g6-iavb4r.css';
import '../../css/b/b1tn-bbru.css';
import '../../css/c/ckuy0x4_i.css';
import '../../css/k/kxk9jzb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kotjj9zeu"/><path class="xt-rj2biq"/><path class="py7p1oj7p"/><path class="g6-iavb4r"/><path class="b1tn-bbru"/><path class="ckuy0x4_i"/><path class="kxk9jzb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-barcode" /></template>
