<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iphe1bwqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-thermostat-sharp" /></template>
<style>
.iphe1bwqa {
  fill: currentColor;
  d: path("m8.36 14.885l2.661-4.698v-.908H7.396v.775h2.735l.03.075l-2.495 4.352zm7.666-.824q.609-.824.609-2.061t-.618-2.06t-1.664-.825q-1.07 0-1.679.824q-.608.824-.608 2.061t.606 2.06t1.676.825t1.678-.824m-1.676.049q-.708 0-1.1-.559T12.858 12q0-.927.4-1.518t1.092-.591t1.092.59t.4 1.519q0 .992-.392 1.551t-1.1.559M12.003 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
