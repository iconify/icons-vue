<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0y4bac_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:percent-rounded" /></template>
<style>
.h0y4bac_i {
  fill: currentColor;
  d: path("M7.827 10.635q-1.171 0-1.999-.828t-.828-2q0-1.17.828-1.998t1.999-.828t1.999.828t.828 1.999t-.828 1.999t-1.999.828m-.001-1q.76 0 1.294-.533t.534-1.293t-.533-1.295t-1.293-.533t-1.294.532Q6 7.046 6 7.806t.533 1.295q.532.533 1.293.533M16.192 19q-1.17 0-1.999-.828q-.827-.828-.827-1.999t.827-1.999t2-.828t1.998.828t.828 1.999t-.828 1.999t-1.999.828m1.294-1.532q.533-.533.533-1.294t-.532-1.294t-1.293-.534t-1.295.533q-.533.532-.533 1.293t.532 1.294t1.293.534t1.295-.533m-12.08.64q0-.208.14-.341L17.804 5.508q.14-.14.335-.131q.194.01.334.15t.14.347t-.14.341L6.216 18.473q-.141.14-.335.13q-.195-.009-.335-.15t-.14-.347");
}

</style>
