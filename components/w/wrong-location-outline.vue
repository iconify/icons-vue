<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5inu8i8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wrong-location-outline" /></template>
<style>
.i5inu8i8u {
  fill: currentColor;
  d: path("M12 21.039q-3.544-3.118-5.33-5.815q-1.785-2.697-1.785-4.908q0-3.174 2.076-5.245T12 3q.157 0 .307.003q.149.003.308.027v.993q-.154-.021-.307-.032q-.154-.01-.308-.01q-2.621 0-4.359 1.795t-1.737 4.54q0 1.851 1.629 4.38Q9.16 17.222 12 19.676q2.762-2.415 4.39-4.895q1.63-2.48 1.687-4.351q0-.012-.003-.023q-.003-.012-.003-.023h1.012q0 .011.007.023q.006.011.006.023q-.057 2.192-1.843 4.86T12 21.038M16.01 7.82l2.1-2.1l2.1 2.1l.707-.708l-2.1-2.1l2.1-2.1l-.707-.707l-2.1 2.1l-2.1-2.1l-.708.707l2.1 2.1l-2.1 2.1zm-2.867 3.436q.473-.475.473-1.143t-.476-1.14t-1.143-.472t-1.14.476t-.472 1.143t.475 1.14t1.144.472t1.14-.476");
}

</style>
