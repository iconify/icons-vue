<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xtvyh10up"/><path class="s532t8spq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tower-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s532t8spq {
  d: path("M17.9986 21.9976H21.9976M17.9986 21.9976V8.0009M17.9986 21.9976H13.9995H10.0005H6.0014M17.9986 8.0009H6.0014M17.9986 8.0009H19.3469C19.8414 8.0009 20.0357 7.3611 19.6242 7.0812L12.2773 2.0824C12.1094 1.9724 11.8906 1.9724 11.7227 2.0824L4.3758 7.0812C3.9643 7.3611 4.1586 8.0009 4.6531 8.0009H6.0014M6.0014 21.9976H2.0024M6.0014 21.9976V8.0009M10.5004 17.9986H13.4996C13.7757 17.9986 13.9995 17.7786 13.9995 17.4987V13.9995C13.9995 12.8998 13.1043 12 12 12C10.8957 12 10.0005 12.8998 10.0005 13.9995V17.4987C10.0005 17.7786 10.2243 17.9986 10.5004 17.9986Z");
}

.xtvyh10up {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.1643 1.2625C11.668 0.9226 12.332 0.9226 12.8357 1.2625L20.1866 6.2614C21.4121 7.0812 20.8277 9.0007 19.3469 9.0007H18.9983V20.9979H21.9976C22.5498 20.9979 22.9973 21.4478 22.9974 21.9976C22.9974 22.5475 22.5498 22.9974 21.9976 22.9974H2.0024C1.4502 22.9974 1.0026 22.5475 1.0026 21.9976C1.0027 21.4478 1.4502 20.9979 2.0024 20.9979H5.0017V9.0007H4.6531C3.1724 9.0007 2.589 7.0812 3.8134 6.2614L11.1643 1.2625Z");
  stroke: none;
}

</style>
